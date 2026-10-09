<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6ghr8bhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z6ghr8bhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:underline-20" {...props}></Icon>
