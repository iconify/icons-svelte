<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4d-6lb0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b4d-6lb0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:socket-check" {...props}></Icon>
