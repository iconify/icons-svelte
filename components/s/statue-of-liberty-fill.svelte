<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxlcok_iq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxlcok_iq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:statue-of-liberty-fill" {...props}></Icon>
