<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llgy7otxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="llgy7otxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:star-fill" {...props}></Icon>
