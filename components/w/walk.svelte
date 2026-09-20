<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl0zh5brt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yl0zh5brt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:walk" {...props}></Icon>
