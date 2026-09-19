<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnp-4onrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xnp-4onrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:sort-down-alt" {...props}></Icon>
