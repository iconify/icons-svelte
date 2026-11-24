<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdi4l-b_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qdi4l-b_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:zap-filled" {...props}></Icon>
