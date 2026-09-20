<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er5zambto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="er5zambto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:timeline" {...props}></Icon>
