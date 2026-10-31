<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oosdismyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oosdismyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:video-camera-x-mark-solid" {...props}></Icon>
