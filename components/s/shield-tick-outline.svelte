<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbiu-lblj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zbiu-lblj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:shield-tick-outline" {...props}></Icon>
