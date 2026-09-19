<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrohoebxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrohoebxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:star-half-solid" {...props}></Icon>
