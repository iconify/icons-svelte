<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htf797bdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="htf797bdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:rss" {...props}></Icon>
