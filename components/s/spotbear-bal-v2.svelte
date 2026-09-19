<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzmf56btu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzmf56btu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:spotbear-bal-v2" {...props}></Icon>
