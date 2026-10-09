<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwdj28vql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zwdj28vql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:uv-index-48-bold" {...props}></Icon>
