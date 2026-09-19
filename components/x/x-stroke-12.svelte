<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mw7s5sw9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="mw7s5sw9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:x-stroke-12" {...props}></Icon>
