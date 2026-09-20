<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il_najbxg.css';
import '../../css/n/n1lsf0bnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<defs><path id="SVG2jlUvrhl" class="il_najbxg"/></defs><g clip-rule="evenodd" class="n1lsf0bnc"><use href="#SVG2jlUvrhl"/><use href="#SVG2jlUvrhl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:send-filled" {...props}></Icon>
