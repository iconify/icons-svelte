<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6cee2x7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6cee2x7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:shield-alt" {...props}></Icon>
