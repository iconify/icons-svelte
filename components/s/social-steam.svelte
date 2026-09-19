<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxcyr-bko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="oxcyr-bko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-steam" {...props}></Icon>
