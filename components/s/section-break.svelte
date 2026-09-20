<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6-7zyeex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p6-7zyeex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:section-break" {...props}></Icon>
