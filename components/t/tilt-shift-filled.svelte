<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmw6fyb9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmw6fyb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:tilt-shift-filled" {...props}></Icon>
