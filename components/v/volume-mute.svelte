<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/my03x_qnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="my03x_qnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:volume-mute" {...props}></Icon>
