<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggxcypbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ggxcypbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:space-bar-20-bold" {...props}></Icon>
