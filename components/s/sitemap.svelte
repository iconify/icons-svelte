<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpiwv57_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qpiwv57_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:sitemap" {...props}></Icon>
