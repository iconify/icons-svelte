<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0tnlimht.css';
import '../../css/x/xc9imsb1x.css';
import '../../css/f/f_84nivhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s0tnlimht"/><path class="xc9imsb1x"/><path class="f_84nivhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:zil" {...props}></Icon>
