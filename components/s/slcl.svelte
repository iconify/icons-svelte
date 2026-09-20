<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpsiuj30w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpsiuj30w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:slcl" {...props}></Icon>
