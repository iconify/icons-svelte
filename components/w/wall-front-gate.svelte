<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnb5g8bpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="rnb5g8bpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:wall-front-gate" {...props}></Icon>
