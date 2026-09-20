<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo07-2dhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wo07-2dhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:webcam-line" {...props}></Icon>
