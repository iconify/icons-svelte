<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdhrm5bky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vdhrm5bky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:tag-filled" {...props}></Icon>
