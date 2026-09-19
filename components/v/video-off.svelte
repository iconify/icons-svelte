<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz4fe1p6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zz4fe1p6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:video-off" {...props}></Icon>
