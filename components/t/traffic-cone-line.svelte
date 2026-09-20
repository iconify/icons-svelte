<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl75c2-_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fl75c2-_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:traffic-cone-line" {...props}></Icon>
