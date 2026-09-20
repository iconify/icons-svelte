<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzx72lvrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzx72lvrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wineglass-2-line" {...props}></Icon>
