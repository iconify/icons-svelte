<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tysv080gv.css';
import '../../css/r/rbu861b0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="tysv080gv"/><path class="rbu861b0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:ticket-alt" {...props}></Icon>
