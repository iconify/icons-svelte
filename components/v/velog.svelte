<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hotlcw4rj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hotlcw4rj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:velog" {...props}></Icon>
