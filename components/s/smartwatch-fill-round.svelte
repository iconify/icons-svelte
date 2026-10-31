<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m542cpb6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m542cpb6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:smartwatch-fill-round" {...props}></Icon>
