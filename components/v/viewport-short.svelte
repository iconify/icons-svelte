<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax3mq91ic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ax3mq91ic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:viewport-short" {...props}></Icon>
