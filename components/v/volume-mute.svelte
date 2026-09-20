<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eripg9b9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="eripg9b9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:volume-mute" {...props}></Icon>
