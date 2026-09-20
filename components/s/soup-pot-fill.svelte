<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xle9labyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xle9labyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:soup-pot-fill" {...props}></Icon>
