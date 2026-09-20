<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bapy_ccxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bapy_ccxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:test-tube-filled" {...props}></Icon>
