<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g81rdnxxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="g81rdnxxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:times-outline" {...props}></Icon>
