<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-157z73m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="x-157z73m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:sc-vimeo" {...props}></Icon>
