<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxpyef0hm.css';
import '../../css/e/ext4fquee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pxpyef0hm"/><path class="ext4fquee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:school-filled" {...props}></Icon>
