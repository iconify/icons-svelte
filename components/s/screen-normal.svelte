<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grv7j-bde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="grv7j-bde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:screen-normal" {...props}></Icon>
