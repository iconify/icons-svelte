<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxc6n7fcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxc6n7fcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:user-check" {...props}></Icon>
