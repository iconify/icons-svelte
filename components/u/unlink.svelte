<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usj0p_4lr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="usj0p_4lr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:unlink" {...props}></Icon>
