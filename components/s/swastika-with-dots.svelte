<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq0_rze8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pq0_rze8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:swastika-with-dots" {...props}></Icon>
