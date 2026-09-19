<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqgpeml1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":24};
const content = `<path class="qqgpeml1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:undo" {...props}></Icon>
