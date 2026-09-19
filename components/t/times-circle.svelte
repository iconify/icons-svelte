<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de5b7ebfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="de5b7ebfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:times-circle" {...props}></Icon>
