<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_oz0_00z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y_oz0_00z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:unlink" {...props}></Icon>
