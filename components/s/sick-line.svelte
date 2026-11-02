<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yohnb-boq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yohnb-boq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sick-line" {...props}></Icon>
