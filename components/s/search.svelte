<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn2k2obiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xn2k2obiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:search" {...props}></Icon>
