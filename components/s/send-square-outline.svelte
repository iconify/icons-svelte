<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v81dzmbmg.css';
import '../../css/s/s7o6tu02b.css';
import '../../css/m/mzfoi9l1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v81dzmbmg"/><path class="s7o6tu02b"/><path clip-rule="evenodd" class="mzfoi9l1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:send-square-outline" {...props}></Icon>
