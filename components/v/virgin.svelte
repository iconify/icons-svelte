<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x__3-1tlm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x__3-1tlm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:virgin" {...props}></Icon>
