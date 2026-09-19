<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfx76kboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfx76kboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:steps-up" {...props}></Icon>
