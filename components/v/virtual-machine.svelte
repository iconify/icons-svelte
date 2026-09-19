<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q73ykcblb.css';
import '../../css/q/qgekv_ybn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q73ykcblb"/><path class="qgekv_ybn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:virtual-machine" {...props}></Icon>
