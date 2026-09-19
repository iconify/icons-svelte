<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjzxa7-xg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yjzxa7-xg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:store-add-01" {...props}></Icon>
