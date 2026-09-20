<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a964un1_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a964un1_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:shield-cross-fill" {...props}></Icon>
