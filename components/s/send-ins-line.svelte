<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spqk0abml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="spqk0abml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:send-ins-line" {...props}></Icon>
