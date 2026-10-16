<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lml3v6bum.css';
import '../../css/w/wgzcd4bsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":57.6,"height":19.5};
const content = `<path class="lml3v6bum"/><path class="wgzcd4bsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:saleor" {...props}></Icon>
