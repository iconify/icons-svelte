<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6gyvvg5u.css';
import '../../css/w/w5la7cbdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f6gyvvg5u"/><path class="w5la7cbdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermal-store-20-bold" {...props}></Icon>
