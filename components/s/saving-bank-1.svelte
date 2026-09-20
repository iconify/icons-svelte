<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_l89u2bx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_l89u2bx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:saving-bank-1" {...props}></Icon>
