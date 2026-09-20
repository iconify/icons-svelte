<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di4cnib-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="di4cnib-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:slash" {...props}></Icon>
