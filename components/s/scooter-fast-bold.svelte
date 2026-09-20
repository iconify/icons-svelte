<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eijcr9bgh.css';
import '../../css/h/h_qr04una.css';
import '../../css/f/ffwokxblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eijcr9bgh"/><path class="h_qr04una"/><path class="ffwokxblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:scooter-fast-bold" {...props}></Icon>
