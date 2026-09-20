<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/w/w3sn9lbrk.css';
import '../../css/h/hf1azzbkc.css';
import '../../css/m/mvgiplmjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w3sn9lbrk"/><path class="hf1azzbkc"/><path clip-rule="evenodd" class="mvgiplmjo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:sticky-notes-duotone" {...props}></Icon>
