<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sarsgtq6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sarsgtq6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:wrench" {...props}></Icon>
