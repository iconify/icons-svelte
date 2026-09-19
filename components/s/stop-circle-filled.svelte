<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e16htrgcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e16htrgcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:stop-circle-filled" {...props}></Icon>
