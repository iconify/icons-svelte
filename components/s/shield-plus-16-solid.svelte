<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3q8zwb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d3q8zwb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:shield-plus-16-solid" {...props}></Icon>
