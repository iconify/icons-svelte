<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnkf2h0mj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mnkf2h0mj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:send-yens" {...props}></Icon>
