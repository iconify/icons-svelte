<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amzh07clk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="amzh07clk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:seahorse" {...props}></Icon>
