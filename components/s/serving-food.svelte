<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs8dtofvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gs8dtofvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:serving-food" {...props}></Icon>
