<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkazv9b8k.css';
import '../../css/g/gkd-s96ca.css';
import '../../css/k/k7imll63p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="jkazv9b8k"/><path class="gkd-s96ca"/><path class="k7imll63p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:unocss" {...props}></Icon>
