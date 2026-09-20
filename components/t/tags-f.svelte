<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu271i46h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"top":-2.5};
const content = `<path class="qu271i46h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:tags-f" {...props}></Icon>
