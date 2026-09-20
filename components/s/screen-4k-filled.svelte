<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdopu7blc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tdopu7blc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:screen-4k-filled" {...props}></Icon>
