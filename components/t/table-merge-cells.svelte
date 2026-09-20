<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox9j4lbjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ox9j4lbjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:table-merge-cells" {...props}></Icon>
