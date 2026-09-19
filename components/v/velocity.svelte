<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvj7pvbyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":457,"height":512};
const content = `<path class="mvj7pvbyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:velocity" {...props}></Icon>
