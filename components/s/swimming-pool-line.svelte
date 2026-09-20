<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnkdo2gun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wnkdo2gun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:swimming-pool-line" {...props}></Icon>
