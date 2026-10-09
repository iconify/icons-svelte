<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7s9a4brn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l7s9a4brn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sun-20-bold" {...props}></Icon>
