<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g892u-omi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g892u-omi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:stop-filled" {...props}></Icon>
