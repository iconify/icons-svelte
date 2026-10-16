<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/japh1-c2n.css';
import '../../css/q/qhxqg70ep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="japh1-c2n"/><path class="qhxqg70ep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:text-search-20-bold" {...props}></Icon>
