<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-ons0b3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q-ons0b3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wind-rose-20-bold" {...props}></Icon>
