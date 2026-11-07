<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edf2mabxb.css';
import '../../css/t/tmi2ocbvf.css';
import '../../css/r/rwz9xbcdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="edf2mabxb"/><path class="tmi2ocbvf"/><path class="rwz9xbcdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-sort-horizontal-bold-duotone" {...props}></Icon>
