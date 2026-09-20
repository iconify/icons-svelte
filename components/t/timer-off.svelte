<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-33o2bhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-33o2bhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:timer-off" {...props}></Icon>
