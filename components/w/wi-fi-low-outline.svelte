<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvlkclb-m.css';
import '../../css/q/qbcnl7b4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jvlkclb-m"/><path class="qbcnl7b4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wi-fi-low-outline" {...props}></Icon>
