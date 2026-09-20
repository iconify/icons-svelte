<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnuym_b7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="qnuym_b7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:steps-2" {...props}></Icon>
