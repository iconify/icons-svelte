<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh09i1btx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gh09i1btx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:transfer-3-fill" {...props}></Icon>
