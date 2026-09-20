<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja39s95eo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ja39s95eo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:upload-2" {...props}></Icon>
