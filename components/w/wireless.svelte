<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz4w4abug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vz4w4abug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:wireless" {...props}></Icon>
