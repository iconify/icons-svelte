<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk-ptcqav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jk-ptcqav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tasmocompiler-light" {...props}></Icon>
