<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh87_f6pu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wh87_f6pu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:user-follow-fill" {...props}></Icon>
