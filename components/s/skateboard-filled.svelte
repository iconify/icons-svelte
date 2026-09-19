<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksw9zbbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ksw9zbbgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:skateboard-filled" {...props}></Icon>
