<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udmlpgjrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udmlpgjrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:scan-face-filled" {...props}></Icon>
