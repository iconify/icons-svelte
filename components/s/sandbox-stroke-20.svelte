<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxp6gm95j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xxp6gm95j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:sandbox-stroke-20" {...props}></Icon>
