<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqd3mo5rx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pqd3mo5rx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:type-hierarchy-sub" {...props}></Icon>
