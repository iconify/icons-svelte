<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmelp6kaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lmelp6kaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:sort-numberic-desc" {...props}></Icon>
