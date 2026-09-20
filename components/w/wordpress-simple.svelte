<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fop6pbdfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fop6pbdfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:wordpress-simple" {...props}></Icon>
