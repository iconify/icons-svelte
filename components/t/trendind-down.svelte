<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp181jb-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bp181jb-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:trendind-down" {...props}></Icon>
