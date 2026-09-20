<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqc487bpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqc487bpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:segment-fill" {...props}></Icon>
