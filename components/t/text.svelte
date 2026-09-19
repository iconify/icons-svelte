<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_w0ioocj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_w0ioocj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:text" {...props}></Icon>
