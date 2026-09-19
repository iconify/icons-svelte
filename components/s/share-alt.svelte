<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwc9hobsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="qwc9hobsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:share-alt" {...props}></Icon>
