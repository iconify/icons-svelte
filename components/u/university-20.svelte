<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t__07qb8r.css';
import '../../css/z/z7w62dbic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t__07qb8r"/><path class="z7w62dbic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:university-20" {...props}></Icon>
