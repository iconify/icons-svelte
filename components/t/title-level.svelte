<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3lph30dl.css';
import '../../css/v/vvq0i9b7z.css';
import '../../css/g/gzw708umu.css';
import '../../css/m/mqnfj0biv.css';
import '../../css/i/i36jpfazz.css';
import '../../css/v/vhf8g-7jc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="vvq0i9b7z"/><path class="gzw708umu"/><path class="mqnfj0biv"/><path class="i36jpfazz"/><path class="vhf8g-7jc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:title-level" {...props}></Icon>
