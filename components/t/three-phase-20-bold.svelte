<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iicur4vle.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iicur4vle"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:three-phase-20-bold" {...props}></Icon>
