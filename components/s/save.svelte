<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk5carb5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="qk5carb5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:save" {...props}></Icon>
