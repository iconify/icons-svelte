<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6cq0z4kl.css';
import '../../css/m/m47_gshyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6cq0z4kl wm-k"/><path class="m47_gshyo wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:shield-alert" {...props}></Icon>
