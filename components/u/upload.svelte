<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni8fv72nb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":32};
const content = `<path class="ni8fv72nb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:upload" {...props}></Icon>
