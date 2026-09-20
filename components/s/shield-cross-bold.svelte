<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxy7-ob-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oxy7-ob-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shield-cross-bold" {...props}></Icon>
