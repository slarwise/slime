# Slime - a data format for communication between (?)

DISCLAIMER: This repo will definitely be biased.

The aim is to stupify data (maybe everything is a string/an image/a sound/a
touch?) so that we (non-specific) can understand each other. If you want to
filter it programmatically/analyze it, you have to figure out that yourself. Is
data analysis really important? Do we standardize stuff to actually understand
each other, or is it mainly to surveil?

## A naive solution

Since this is a code repository, I kind of have to interact with a computer. We
usually (source needed, is this the only way?) do this with text. So let's say I
want to communicate that my name is Arvid. Let's tell that to the computer with
text, and then output the text in a human-readable (non-specific, biased surely)
way, as an image, as a sound, how as a touch? I can at least make it so that I
can understand it myself in multiple ways.

## API

It is limiting to only have ONE way of storing data. It should be up to everyone
to decide that themselves. Hmmm. I'm biased to text so I'll go with that.

## Input

```programming-language
outputs = transform_subjectively(input);
```

## Example

```programming-language
text, image, sound, touch, video = transform_subjectively("My name is Arvid");
```

## TODO

- What research are there regarding non-analyzable data, if that is a term? That
  sounds like a cool thing to have. Can't be analyzed, but still understood and
  translated by humans/non-computers/need better definition.
- What about AI? If it is good, can it still understand me? Is that
  good/bad/neutral/a secret fourth thing?
- Why are images usually rectangular?
- I am using markdown, lol.
