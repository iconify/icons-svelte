<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_s4ql23r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j_s4ql23r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:sort-amount-down" {...props}></Icon>
