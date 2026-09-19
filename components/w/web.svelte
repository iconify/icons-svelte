<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvn2keyzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="vvn2keyzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:web" {...props}></Icon>
