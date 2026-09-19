<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1acuibhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f1acuibhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:symbol-property" {...props}></Icon>
