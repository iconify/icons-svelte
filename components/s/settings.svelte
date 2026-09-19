<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okput2b5x.css';
import '../../css/n/n4gtcv7gc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="okput2b5x"/><path class="n4gtcv7gc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:settings" {...props}></Icon>
