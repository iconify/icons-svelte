<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk_e4zb4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lk_e4zb4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:shapes-solid" {...props}></Icon>
