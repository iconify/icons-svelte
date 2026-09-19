<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzxtc-bwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dzxtc-bwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:stoplights-fill" {...props}></Icon>
