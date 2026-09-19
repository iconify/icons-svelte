<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y359-tbfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y359-tbfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:usdt" {...props}></Icon>
