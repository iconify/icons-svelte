<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd6if1b-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="qd6if1b-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:wifi-1-filled" {...props}></Icon>
