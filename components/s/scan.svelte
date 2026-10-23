<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6aj5rteo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m6aj5rteo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:scan" {...props}></Icon>
