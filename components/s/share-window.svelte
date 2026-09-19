<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny2u-nb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ny2u-nb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:share-window" {...props}></Icon>
