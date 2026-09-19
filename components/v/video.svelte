<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6a1je0ov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r6a1je0ov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:video" {...props}></Icon>
