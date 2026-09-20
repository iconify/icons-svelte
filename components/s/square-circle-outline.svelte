<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yil66vogh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yil66vogh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:square-circle-outline" {...props}></Icon>
