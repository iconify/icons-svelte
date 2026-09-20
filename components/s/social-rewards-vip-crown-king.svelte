<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ricfbrb2c.css';
import '../../css/g/g4qqy3bgi.css';
import '../../css/y/yiwpdobhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ricfbrb2c"/><path class="g4qqy3bgi"/><path class="yiwpdobhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:social-rewards-vip-crown-king" {...props}></Icon>
