<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee-9a1ddt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ee-9a1ddt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:star-outline" {...props}></Icon>
