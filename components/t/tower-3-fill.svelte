<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp7sqsb5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qp7sqsb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tower-3-fill" {...props}></Icon>
