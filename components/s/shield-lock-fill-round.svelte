<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad6t1ls9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ad6t1ls9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shield-lock-fill-round" {...props}></Icon>
