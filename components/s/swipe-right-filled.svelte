<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlrh_nuyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zlrh_nuyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:swipe-right-filled" {...props}></Icon>
