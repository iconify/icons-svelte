<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj6eepmbw.css';
import '../../css/m/m-0zmcczs.css';
import '../../css/x/x9ach8b5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<rect class="dj6eepmbw"/><path class="m-0zmcczs"/><path class="x9ach8b5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:tennis" {...props}></Icon>
