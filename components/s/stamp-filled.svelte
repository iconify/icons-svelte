<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-7shwbjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-7shwbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:stamp-filled" {...props}></Icon>
