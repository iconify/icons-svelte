<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4ijmfbcv.css';
import '../../css/d/dj_p1sbgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v4ijmfbcv"/><path class="dj_p1sbgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:stumbleupon" {...props}></Icon>
