<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyvwjobrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hyvwjobrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:triangle-up-outline" {...props}></Icon>
