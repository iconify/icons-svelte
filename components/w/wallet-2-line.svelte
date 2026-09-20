<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjaafrboq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gjaafrboq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:wallet-2-line" {...props}></Icon>
