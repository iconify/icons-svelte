<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3kt8y1qb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="b3kt8y1qb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:shoe-prints" {...props}></Icon>
