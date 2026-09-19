<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7s__0boc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c7s__0boc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:share-two" {...props}></Icon>
