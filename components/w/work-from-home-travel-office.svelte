<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtud3ynqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mtud3ynqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:work-from-home-travel-office" {...props}></Icon>
