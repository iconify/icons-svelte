<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe24tacqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qe24tacqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:wechat-pay-logo-block" {...props}></Icon>
