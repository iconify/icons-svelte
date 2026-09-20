<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_gu4ob0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_gu4ob0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:user-warning-outline" {...props}></Icon>
