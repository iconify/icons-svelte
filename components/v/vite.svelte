<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v89hnb0kp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":510,"height":512};
const content = `<path class="v89hnb0kp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:vite" {...props}></Icon>
