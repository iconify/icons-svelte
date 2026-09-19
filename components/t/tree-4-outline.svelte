<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypweetshz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ypweetshz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tree-4-outline" {...props}></Icon>
