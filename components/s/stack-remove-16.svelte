<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifoyfinjb.css';
import '../../css/p/pxi__8h-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ifoyfinjb"/><path clip-rule="evenodd" class="pxi__8h-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:stack-remove-16" {...props}></Icon>
