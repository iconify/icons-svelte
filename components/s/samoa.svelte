<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdftbpbaj.css';
import '../../css/j/j4lu8gyen.css';
import '../../css/q/qmrxzvmyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="wdftbpbaj"/><path class="j4lu8gyen"/><path class="qmrxzvmyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:samoa" {...props}></Icon>
