<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vifm8s9hx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vifm8s9hx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:suitcase-xray" {...props}></Icon>
