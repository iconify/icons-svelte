<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/saj7vdbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="saj7vdbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:volleyball-ball-solid" {...props}></Icon>
