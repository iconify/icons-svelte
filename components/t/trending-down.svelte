<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vktmc_wue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vktmc_wue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:trending-down" {...props}></Icon>
