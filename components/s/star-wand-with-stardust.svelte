<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg0kydbza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tg0kydbza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:star-wand-with-stardust" {...props}></Icon>
