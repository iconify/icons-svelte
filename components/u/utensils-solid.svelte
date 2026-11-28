<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obc5yvguy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="obc5yvguy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:utensils-solid" {...props}></Icon>
