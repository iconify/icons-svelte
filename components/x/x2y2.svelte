<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km06l1bkk.css';
import '../../css/h/hh9pgq2kj.css';
import '../../css/r/r6o281qjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="km06l1bkk"/><path class="hh9pgq2kj"/><path clip-rule="evenodd" class="r6o281qjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:x2y2" {...props}></Icon>
