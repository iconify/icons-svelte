<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqzirr-9x.css';
import '../../css/y/y8ad7wc8w.css';
import '../../css/r/rub25_bgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zqzirr-9x"/><path class="y8ad7wc8w"/><path class="rub25_bgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:salt-cavern-48-bold" {...props}></Icon>
