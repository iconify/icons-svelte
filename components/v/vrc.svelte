<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg2o5wied.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rg2o5wied"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:vrc" {...props}></Icon>
