<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy2ew1bow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sy2ew1bow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:todoist" {...props}></Icon>
