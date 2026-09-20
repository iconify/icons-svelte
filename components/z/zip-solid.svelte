<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh7f1hoyt.css';
import '../../css/m/mmgfxwbmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bh7f1hoyt"/><path clip-rule="evenodd" class="mmgfxwbmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:zip-solid" {...props}></Icon>
