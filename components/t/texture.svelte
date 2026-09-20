<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffevzz76e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ffevzz76e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:texture" {...props}></Icon>
