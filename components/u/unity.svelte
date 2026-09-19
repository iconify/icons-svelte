<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/goem8ebtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":23,"height":24};
const content = `<path class="goem8ebtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:unity" {...props}></Icon>
