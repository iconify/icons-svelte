<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rynbiubyg.css';
import '../../css/d/dojgfibbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":24};
const content = `<path class="rynbiubyg"/><path class="dojgfibbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:spinner-fidget" {...props}></Icon>
