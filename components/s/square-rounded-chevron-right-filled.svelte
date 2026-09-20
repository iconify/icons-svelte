<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8l77y5we.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8l77y5we"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-chevron-right-filled" {...props}></Icon>
