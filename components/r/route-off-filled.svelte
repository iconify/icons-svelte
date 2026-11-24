<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8jmy1b5l.css';
import '../../css/u/ur5d4xvrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y8jmy1b5l"/><path class="ur5d4xvrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:route-off-filled" {...props}></Icon>
