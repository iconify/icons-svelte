<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le_5x_bsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="le_5x_bsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:scarf-fill" {...props}></Icon>
