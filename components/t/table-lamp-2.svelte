<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwexrpbzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="rwexrpbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:table-lamp-2" {...props}></Icon>
