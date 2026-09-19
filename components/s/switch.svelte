<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gc-j51bxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gc-j51bxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:switch" {...props}></Icon>
