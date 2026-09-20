<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2ser0o3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="k2ser0o3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:table-top-stairs-down" {...props}></Icon>
