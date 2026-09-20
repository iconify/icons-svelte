<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq_ejxr3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sq_ejxr3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:square-solid" {...props}></Icon>
