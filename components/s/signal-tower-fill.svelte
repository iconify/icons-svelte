<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ciy968brf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ciy968brf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:signal-tower-fill" {...props}></Icon>
