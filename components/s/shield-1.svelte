<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eifsnebhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="eifsnebhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:shield-1" {...props}></Icon>
