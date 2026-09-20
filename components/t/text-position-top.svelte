<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uttz4dh8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uttz4dh8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:text-position-top" {...props}></Icon>
