<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mplvu4bxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mplvu4bxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:stop" {...props}></Icon>
