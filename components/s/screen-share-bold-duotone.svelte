<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aof5xebnh.css';
import '../../css/i/i2cm9bb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aof5xebnh"/><path clip-rule="evenodd" class="i2cm9bb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:screen-share-bold-duotone" {...props}></Icon>
