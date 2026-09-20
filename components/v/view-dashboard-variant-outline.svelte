<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpf1o5bnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qpf1o5bnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:view-dashboard-variant-outline" {...props}></Icon>
