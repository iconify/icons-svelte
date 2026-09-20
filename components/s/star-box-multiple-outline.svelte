<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-3jc2mnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-3jc2mnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:star-box-multiple-outline" {...props}></Icon>
