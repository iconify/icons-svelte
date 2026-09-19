<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/poeaz65-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="poeaz65-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:scale-unbalanced" {...props}></Icon>
