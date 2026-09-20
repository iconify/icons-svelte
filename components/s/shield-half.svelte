<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5exlyb4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i5exlyb4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:shield-half" {...props}></Icon>
