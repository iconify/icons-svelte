<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb2y1ebum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="eb2y1ebum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:tooltip-start-alert" {...props}></Icon>
