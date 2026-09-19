<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnlnjbcmb.css';
import '../../css/e/exdnk9b2b.css';
import '../../css/z/z1jg2ibea.css';
import '../../css/j/jiqf9lbqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mnlnjbcmb"/><path class="exdnk9b2b"/><path class="z1jg2ibea"/><path class="jiqf9lbqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:save-annotation" {...props}></Icon>
