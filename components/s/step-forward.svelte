<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/roc7g_b5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="roc7g_b5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:step-forward" {...props}></Icon>
