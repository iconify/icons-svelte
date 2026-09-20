<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auvu2r1ra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="auvu2r1ra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sofa-fill" {...props}></Icon>
