<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fewaveakl.css';
import '../../css/k/ky4905xsu.css';
import '../../css/z/znvvmubwx.css';
import '../../css/m/m2te1-oby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fewaveakl"/><path class="ky4905xsu"/><path class="znvvmubwx"/><path class="m2te1-oby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:rwn" {...props}></Icon>
