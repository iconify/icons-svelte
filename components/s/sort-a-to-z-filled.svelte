<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eeem824ht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="eeem824ht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:sort-a-to-z-filled" {...props}></Icon>
