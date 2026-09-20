<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpq6t6b2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="bpq6t6b2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:times" {...props}></Icon>
