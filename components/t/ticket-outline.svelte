<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbucpsg1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbucpsg1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ticket-outline" {...props}></Icon>
