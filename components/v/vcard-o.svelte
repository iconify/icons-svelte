<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1h895bzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":1536};
const content = `<path class="b1h895bzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:vcard-o" {...props}></Icon>
