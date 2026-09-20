<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kg4ikjusu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kg4ikjusu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:user-round" {...props}></Icon>
