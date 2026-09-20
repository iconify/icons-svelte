<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm21li_zz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pm21li_zz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:signpost-big" {...props}></Icon>
