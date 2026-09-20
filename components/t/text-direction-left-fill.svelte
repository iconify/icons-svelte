<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plfbs3b-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="plfbs3b-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:text-direction-left-fill" {...props}></Icon>
