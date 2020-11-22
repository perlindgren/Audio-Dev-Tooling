# Audio Dev Tooling

---

## Linux Tooling (tested under Manjaro/arch)

---

### usb related

- lsusb -t
  
  Tree view of 

---

### Alsa related

- aplay -l 

  list of PLAYBACK Hardware Devices

- amidi -l

  list of midi devices

- aseqdump -l
  
  list of alsa (sequencer) ports

- aseqdump -p 28

  dumps midi events on port (28 in this case)

---

## Apple OSX (tested under High Sierra 10.13.6)

### usb related

---

## Resources and documentation

- [midi 1.0](https://www.usb.org/sites/default/files/midi10.pdf)
- [Silab USB AUDIO CLASS TUTORIAL](https://www.silabs.com/documents/public/application-notes/AN295.pdf)