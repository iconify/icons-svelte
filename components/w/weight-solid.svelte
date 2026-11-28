<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppp-ntbmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ppp-ntbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:weight-solid" {...props}></Icon>
