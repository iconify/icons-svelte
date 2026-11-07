<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shc5ox2kp.css';
import '../../css/k/kkisrcdox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="shc5ox2kp"/><path clip-rule="evenodd" class="kkisrcdox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:running-bold" {...props}></Icon>
