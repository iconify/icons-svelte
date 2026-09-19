<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eefks2b2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eefks2b2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:umbrella" {...props}></Icon>
