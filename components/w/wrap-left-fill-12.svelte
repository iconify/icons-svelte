<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knc4mgb-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="knc4mgb-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:wrap-left-fill-12" {...props}></Icon>
