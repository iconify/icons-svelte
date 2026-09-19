<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qx_4fpbja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":24};
const content = `<path class="qx_4fpbja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:test-bottle" {...props}></Icon>
