<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dh4gsqbpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="dh4gsqbpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:upright" {...props}></Icon>
