<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogq3rih2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ogq3rih2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:square-outline" {...props}></Icon>
