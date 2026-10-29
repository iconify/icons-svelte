<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6f8krbjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6f8krbjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:test-tube-solid" {...props}></Icon>
