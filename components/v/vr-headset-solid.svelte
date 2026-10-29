<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/heb0llboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="heb0llboh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:vr-headset-solid" {...props}></Icon>
