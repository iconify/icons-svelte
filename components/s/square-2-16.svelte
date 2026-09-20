<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1edu7bqk.css';
import '../../css/m/mf8977brh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="z1edu7bqk"/><path clip-rule="evenodd" class="mf8977brh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:square-2-16" {...props}></Icon>
