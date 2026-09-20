<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac4no8brn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ac4no8brn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ubisoft" {...props}></Icon>
