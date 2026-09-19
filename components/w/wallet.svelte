<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if33038gm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="if33038gm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:wallet" {...props}></Icon>
