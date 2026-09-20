<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru49qvb2s.css';
import '../../css/i/i6xqw31vr.css';
import '../../css/e/e_po1hivt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGdBSpGe6g" x1="13.866" x2="498.134" y1="256" y2="256" gradientUnits="userSpaceOnUse"><stop offset="0" class="ru49qvb2s"/><stop offset="1" class="i6xqw31vr"/></linearGradient><path fill="url(#SVGdBSpGe6g)" class="e_po1hivt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:trek" {...props}></Icon>
