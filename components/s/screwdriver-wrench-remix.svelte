<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwemq-b_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nwemq-b_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:screwdriver-wrench-remix" {...props}></Icon>
