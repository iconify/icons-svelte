<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ey756c4jo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ey756c4jo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-number-7-filled" {...props}></Icon>
