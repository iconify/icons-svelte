<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aem1l6blz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="aem1l6blz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:tooltip-start-text" {...props}></Icon>
