<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvv_ktbyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mvv_ktbyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tree-round" {...props}></Icon>
