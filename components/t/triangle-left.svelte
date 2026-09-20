<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-vmj1b7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q-vmj1b7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:triangle-left" {...props}></Icon>
