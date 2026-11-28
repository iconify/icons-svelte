<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vph8hpb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vph8hpb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:scatter-chart" {...props}></Icon>
