<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iedl4rwbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iedl4rwbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:rpx" {...props}></Icon>
