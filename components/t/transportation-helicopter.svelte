<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy9fe6p_r.css';
import '../../css/x/xtw0f8b2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gy9fe6p_r"/><path class="xtw0f8b2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:transportation-helicopter" {...props}></Icon>
