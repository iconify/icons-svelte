<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe4t69j8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oe4t69j8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:symbol-method" {...props}></Icon>
