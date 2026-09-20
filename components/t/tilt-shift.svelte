<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvky0jspj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvky0jspj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:tilt-shift" {...props}></Icon>
