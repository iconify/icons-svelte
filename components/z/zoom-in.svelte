<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhetqw70i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhetqw70i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:zoom-in" {...props}></Icon>
