<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl63q0_6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yl63q0_6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:server-line" {...props}></Icon>
