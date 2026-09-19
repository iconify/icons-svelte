<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4fyi_b6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o4fyi_b6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:share" {...props}></Icon>
