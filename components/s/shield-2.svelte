<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn-591bve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="jn-591bve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:shield-2" {...props}></Icon>
