<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjfal4j5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sjfal4j5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:toilet-man-flat" {...props}></Icon>
