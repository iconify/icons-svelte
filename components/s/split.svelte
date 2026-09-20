<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec0qbjmvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ec0qbjmvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:split" {...props}></Icon>
