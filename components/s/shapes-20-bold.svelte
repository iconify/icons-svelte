<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1gs6kbwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l1gs6kbwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shapes-20-bold" {...props}></Icon>
