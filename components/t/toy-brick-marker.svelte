<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qokabookt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qokabookt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:toy-brick-marker" {...props}></Icon>
