<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5s6qqfcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h5s6qqfcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:user-4-fill" {...props}></Icon>
