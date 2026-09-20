<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6cxkxoqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t6cxkxoqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:volume-minus-solid" {...props}></Icon>
