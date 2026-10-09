<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtgyfug1i.css';
import '../../css/a/an0ow8eva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xtgyfug1i"/><path class="an0ow8eva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sea-level-rise-20-bold" {...props}></Icon>
