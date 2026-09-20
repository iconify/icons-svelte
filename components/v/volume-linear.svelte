<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa2lxj40u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xa2lxj40u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:volume-linear" {...props}></Icon>
