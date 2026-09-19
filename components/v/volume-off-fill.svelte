<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irpme3b0m.css';
import '../../css/h/hetvd6utf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="irpme3b0m"/><path class="hetvd6utf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:volume-off-fill" {...props}></Icon>
