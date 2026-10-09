<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu6mrmzlt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mu6mrmzlt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sigma-20" {...props}></Icon>
