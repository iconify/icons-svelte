<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd_eumbxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vd_eumbxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:user-plus" {...props}></Icon>
