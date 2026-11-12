<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9qoumbuq.css';
import '../../css/b/batz7rxuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c9qoumbuq"/><path class="batz7rxuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wiredoor-light" {...props}></Icon>
