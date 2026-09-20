<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvb01wb4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvb01wb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-f0-filled" {...props}></Icon>
