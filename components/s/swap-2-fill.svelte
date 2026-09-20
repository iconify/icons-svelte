<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5xmveh_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h5xmveh_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:swap-2-fill" {...props}></Icon>
