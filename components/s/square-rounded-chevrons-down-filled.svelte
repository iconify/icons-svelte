<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4dzfdc3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4dzfdc3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-chevrons-down-filled" {...props}></Icon>
