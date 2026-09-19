<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqls33b8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gqls33b8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:squares-2x2-16-solid" {...props}></Icon>
