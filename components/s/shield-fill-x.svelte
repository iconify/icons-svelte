<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpsb7fehx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cpsb7fehx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:shield-fill-x" {...props}></Icon>
