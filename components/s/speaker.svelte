<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-li6vbct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="g-li6vbct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:speaker" {...props}></Icon>
