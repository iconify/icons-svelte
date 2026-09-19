<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjpvszedz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="yjpvszedz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:viadeo-square" {...props}></Icon>
