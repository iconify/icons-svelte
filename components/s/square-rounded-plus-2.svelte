<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c76d4sb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c76d4sb7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-plus-2" {...props}></Icon>
