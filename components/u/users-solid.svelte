<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-s7vmbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-s7vmbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:users-solid" {...props}></Icon>
