<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1p4-imiy.css';
import '../../css/f/fbmp7wgwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k1p4-imiy"/><path class="fbmp7wgwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:user-clock" {...props}></Icon>
