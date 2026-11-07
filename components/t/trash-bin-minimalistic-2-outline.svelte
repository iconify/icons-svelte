<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/loc47zw8p.css';
import '../../css/f/fib6k6-vs.css';
import '../../css/q/q37ppubrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="loc47zw8p"/><path class="fib6k6-vs"/><path class="q37ppubrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:trash-bin-minimalistic-2-outline" {...props}></Icon>
