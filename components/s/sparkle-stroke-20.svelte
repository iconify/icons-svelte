<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsc05bbuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xsc05bbuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:sparkle-stroke-20" {...props}></Icon>
