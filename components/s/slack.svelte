<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9ul1n1-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9ul1n1-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:slack" {...props}></Icon>
