<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwqe-pb-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwqe-pb-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:wyzecam" {...props}></Icon>
