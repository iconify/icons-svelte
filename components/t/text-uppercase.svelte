<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mft06ikyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mft06ikyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:text-uppercase" {...props}></Icon>
