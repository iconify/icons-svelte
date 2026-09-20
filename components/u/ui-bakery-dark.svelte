<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_jzqe7zd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y_jzqe7zd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ui-bakery-dark" {...props}></Icon>
