<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_8guc_or.css';
import '../../css/h/hfozezxow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z_8guc_or"/><path class="hfozezxow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:straightruler" {...props}></Icon>
