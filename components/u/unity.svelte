<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucft0wbll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ucft0wbll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:unity" {...props}></Icon>
