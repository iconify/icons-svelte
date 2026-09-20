<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjxi_ac1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qjxi_ac1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shield-lock-open" {...props}></Icon>
