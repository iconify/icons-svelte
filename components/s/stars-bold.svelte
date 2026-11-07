<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb0xcujan.css';
import '../../css/u/uxqwpab0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gb0xcujan"/><path class="uxqwpab0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:stars-bold" {...props}></Icon>
