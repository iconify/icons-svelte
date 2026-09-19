<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs_kyl4fj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cs_kyl4fj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:toaster-filled" {...props}></Icon>
