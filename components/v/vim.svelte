<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olbm6ob8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="olbm6ob8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:vim" {...props}></Icon>
