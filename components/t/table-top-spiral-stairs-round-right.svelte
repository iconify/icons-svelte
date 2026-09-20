<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umf1v3cjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="umf1v3cjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:table-top-spiral-stairs-round-right" {...props}></Icon>
