<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igo_o-d5w.css';
import '../../css/d/dnmne6b8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="igo_o-d5w"/><path class="dnmne6b8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:time" {...props}></Icon>
