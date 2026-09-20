<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5igb5bkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p5igb5bkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:user-temporary-ltr" {...props}></Icon>
