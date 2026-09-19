<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv2mi3g-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cv2mi3g-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:thunder-filled" {...props}></Icon>
