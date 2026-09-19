<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er0rbpczb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="er0rbpczb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:shield-filled" {...props}></Icon>
