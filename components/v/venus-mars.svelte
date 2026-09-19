<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl8vzkbjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":27,"height":24};
const content = `<path class="gl8vzkbjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:venus-mars" {...props}></Icon>
