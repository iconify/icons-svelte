<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o605f_yot.css';
import '../../css/c/ce7aadsur.css';
import '../../css/w/wczsurb_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o605f_yot"/><path class="ce7aadsur"/><path class="wczsurb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:warning-alt-filled" {...props}></Icon>
