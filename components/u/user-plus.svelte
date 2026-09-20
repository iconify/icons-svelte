<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjorfy6hs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xjorfy6hs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:user-plus" {...props}></Icon>
