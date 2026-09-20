<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btpnc1bja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="btpnc1bja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:topdotgg" {...props}></Icon>
