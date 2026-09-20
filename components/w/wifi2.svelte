<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9rw8nrxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="c9rw8nrxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:wifi2" {...props}></Icon>
