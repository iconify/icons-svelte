<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzqt8ge1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yzqt8ge1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:star-of-life-solid" {...props}></Icon>
