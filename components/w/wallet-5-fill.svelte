<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z82u35bbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z82u35bbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wallet-5-fill" {...props}></Icon>
