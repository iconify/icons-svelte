<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee4-h3bwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ee4-h3bwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:spray-can" {...props}></Icon>
