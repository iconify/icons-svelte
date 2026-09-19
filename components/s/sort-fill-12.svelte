<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oevo7ab1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="oevo7ab1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:sort-fill-12" {...props}></Icon>
