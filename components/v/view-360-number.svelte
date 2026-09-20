<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frerr6bix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frerr6bix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:view-360-number" {...props}></Icon>
