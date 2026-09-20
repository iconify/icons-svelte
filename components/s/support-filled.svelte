<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z43h6nbwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z43h6nbwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:support-filled" {...props}></Icon>
