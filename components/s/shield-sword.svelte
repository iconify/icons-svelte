<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuiv1f9nq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uuiv1f9nq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shield-sword" {...props}></Icon>
