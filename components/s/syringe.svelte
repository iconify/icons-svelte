<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5xqg8b3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n5xqg8b3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:syringe" {...props}></Icon>
