<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyvovxt3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pyvovxt3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sock-line" {...props}></Icon>
