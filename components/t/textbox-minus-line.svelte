<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr-5j_b8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mr-5j_b8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:textbox-minus-line" {...props}></Icon>
