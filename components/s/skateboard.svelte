<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/u1ns8nbeg.css';
import '../../css/t/t63j1rbwi.css';
import '../../css/i/ic1sxvw3g.css';
import '../../css/z/zlcqyybkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="u1ns8nbeg"/><path class="t63j1rbwi"/><path class="ic1sxvw3g"/><path clip-rule="evenodd" class="zlcqyybkr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:skateboard" {...props}></Icon>
