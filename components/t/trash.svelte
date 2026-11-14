<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um-6ycezm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="um-6ycezm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:trash" {...props}></Icon>
