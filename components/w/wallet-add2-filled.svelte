<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox9uvpbrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ox9uvpbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:wallet-add2-filled" {...props}></Icon>
