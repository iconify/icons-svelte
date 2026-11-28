<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7bv47brn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary t7bv47brn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:star-duotone" {...props}></Icon>
