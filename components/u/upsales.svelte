<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eez8o0bsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":90,"height":22};
const content = `<path class="eez8o0bsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:upsales" {...props}></Icon>
