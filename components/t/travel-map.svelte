<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya239x24v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ya239x24v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:travel-map" {...props}></Icon>
