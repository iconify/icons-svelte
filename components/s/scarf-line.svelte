<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itm8r4buq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itm8r4buq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:scarf-line" {...props}></Icon>
