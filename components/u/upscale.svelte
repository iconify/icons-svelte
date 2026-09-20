<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_hijlbpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_hijlbpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:upscale" {...props}></Icon>
