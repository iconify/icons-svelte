<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kad0u6noq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kad0u6noq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:shop" {...props}></Icon>
