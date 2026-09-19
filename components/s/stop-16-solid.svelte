<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol9rll3qo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<rect class="ol9rll3qo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:stop-16-solid" {...props}></Icon>
