<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1s6giw4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="b1s6giw4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:shield-stroke-12" {...props}></Icon>
