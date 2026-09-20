<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oys3y2b6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oys3y2b6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:sun-low-filled" {...props}></Icon>
