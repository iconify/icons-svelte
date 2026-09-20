<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uen7qn_0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uen7qn_0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:starburst-minus-outline" {...props}></Icon>
