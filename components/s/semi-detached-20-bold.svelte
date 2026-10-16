<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdcnnnb3n.css';
import '../../css/x/xxc3j4pon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gdcnnnb3n"/><path class="xxc3j4pon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:semi-detached-20-bold" {...props}></Icon>
