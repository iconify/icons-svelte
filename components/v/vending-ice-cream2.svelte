<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_3ltgb8o.css';
import '../../css/t/t8j1ap9bj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s_3ltgb8o"/><path class="t8j1ap9bj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:vending-ice-cream2" {...props}></Icon>
