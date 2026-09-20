<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ki7ru6gfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ki7ru6gfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:wwise" {...props}></Icon>
