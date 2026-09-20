<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km_r55b0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="km_r55b0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:village" {...props}></Icon>
