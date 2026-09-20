<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brs95qb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="brs95qb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:spring" {...props}></Icon>
