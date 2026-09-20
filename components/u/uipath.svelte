<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m209dob5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m209dob5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:uipath" {...props}></Icon>
