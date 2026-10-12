<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apoais73k.css';
import '../../css/t/t5r6riq5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="apoais73k"/><path class="t5r6riq5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:wrap-left-fill-20" {...props}></Icon>
