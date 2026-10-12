<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytenn3bqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ytenn3bqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:terminal-stroke-20" {...props}></Icon>
