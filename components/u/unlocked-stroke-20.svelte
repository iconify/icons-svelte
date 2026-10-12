<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fel8-rbzx.css';
import '../../css/q/qtj15rupr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fel8-rbzx"/><path class="qtj15rupr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:unlocked-stroke-20" {...props}></Icon>
