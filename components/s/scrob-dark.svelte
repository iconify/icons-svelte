<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfedm6bzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yfedm6bzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:scrob-dark" {...props}></Icon>
