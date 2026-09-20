<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s69z1x1zm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s69z1x1zm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:skip-forward-fill" {...props}></Icon>
