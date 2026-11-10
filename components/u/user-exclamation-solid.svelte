<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu_817jpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zu_817jpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:user-exclamation-solid" {...props}></Icon>
