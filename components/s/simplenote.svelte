<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbj_h5bon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":488};
const content = `<path class="wbj_h5bon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:simplenote" {...props}></Icon>
