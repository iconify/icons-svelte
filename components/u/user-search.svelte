<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1ra4ravg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1ra4ravg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:user-search" {...props}></Icon>
