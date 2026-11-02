<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3rwrpbup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a3rwrpbup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:siri-fill" {...props}></Icon>
