<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd_1g2ahb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yd_1g2ahb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ynab-dark" {...props}></Icon>
