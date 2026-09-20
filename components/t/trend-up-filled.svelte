<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyxdxf-af.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nyxdxf-af"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:trend-up-filled" {...props}></Icon>
