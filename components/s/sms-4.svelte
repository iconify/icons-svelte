<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brm49pdsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="brm49pdsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:sms-4" {...props}></Icon>
