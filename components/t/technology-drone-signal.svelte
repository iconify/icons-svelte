<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdygn-ngl.css';
import '../../css/h/hq8skxj4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cdygn-ngl"/><path class="hq8skxj4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:technology-drone-signal" {...props}></Icon>
