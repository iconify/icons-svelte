<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5nmv_b-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5nmv_b-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:window-sensor" {...props}></Icon>
