<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg8r7mbnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eg8r7mbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:viewfinder-off" {...props}></Icon>
