<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhexb2biq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhexb2biq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:wearos" {...props}></Icon>
