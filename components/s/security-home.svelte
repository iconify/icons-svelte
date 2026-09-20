<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qje9khszt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qje9khszt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:security-home" {...props}></Icon>
