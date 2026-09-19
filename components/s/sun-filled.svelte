<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gar44446z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gar44446z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:sun-filled" {...props}></Icon>
