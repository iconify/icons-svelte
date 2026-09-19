<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd8gyrktq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="yd8gyrktq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:user-cog" {...props}></Icon>
