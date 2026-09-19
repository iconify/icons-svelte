<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yi64b0bch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":560,"height":840};
const content = `<path class="yi64b0bch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:unlock" {...props}></Icon>
