<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1zp3dnvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1zp3dnvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:vector-difference" {...props}></Icon>
