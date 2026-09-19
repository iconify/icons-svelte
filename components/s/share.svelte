<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz0akj-mt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yz0akj-mt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:share" {...props}></Icon>
