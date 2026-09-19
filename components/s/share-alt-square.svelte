<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v15o35bms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="v15o35bms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:share-alt-square" {...props}></Icon>
