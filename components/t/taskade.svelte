<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffuyh2zgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ffuyh2zgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:taskade" {...props}></Icon>
