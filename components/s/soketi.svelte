<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it6b2o5on.css';
import '../../css/z/znj3s6bsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1314.4,"height":1314.4,"left":340.8,"top":342.8};
const content = `<path class="it6b2o5on"/><path class="znj3s6bsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:soketi" {...props}></Icon>
