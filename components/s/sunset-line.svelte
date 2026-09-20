<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrh1ln4gp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrh1ln4gp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sunset-line" {...props}></Icon>
