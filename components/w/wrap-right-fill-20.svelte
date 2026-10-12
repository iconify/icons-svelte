<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb6ciacld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bb6ciacld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:wrap-right-fill-20" {...props}></Icon>
