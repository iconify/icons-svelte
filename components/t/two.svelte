<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8u14tbgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e8u14tbgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:two" {...props}></Icon>
