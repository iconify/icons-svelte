<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pslwm0o8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pslwm0o8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:stop-small-solid" {...props}></Icon>
