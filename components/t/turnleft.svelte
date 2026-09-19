<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o73s2d9-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="o73s2d9-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:turnleft" {...props}></Icon>
