<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xka43fg1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xka43fg1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-dashed-linear" {...props}></Icon>
