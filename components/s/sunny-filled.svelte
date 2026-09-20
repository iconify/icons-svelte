<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/deqv_pbwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="deqv_pbwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:sunny-filled" {...props}></Icon>
