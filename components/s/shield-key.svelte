<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-yns4hsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-yns4hsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shield-key" {...props}></Icon>
