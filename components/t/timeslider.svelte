<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qovuu4yaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qovuu4yaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:timeslider" {...props}></Icon>
