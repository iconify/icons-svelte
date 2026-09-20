<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uep79_o_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="uep79_o_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:scissors-flat" {...props}></Icon>
