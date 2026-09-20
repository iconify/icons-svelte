<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjcnumbvg.css';
import '../../css/h/h5tf6mlqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xjcnumbvg"/><path class="h5tf6mlqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:technology-innovation-institute-falcon" {...props}></Icon>
