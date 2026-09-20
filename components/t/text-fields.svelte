<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5gtxdbrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h5gtxdbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:text-fields" {...props}></Icon>
