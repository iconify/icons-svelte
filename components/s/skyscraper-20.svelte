<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1l3kib5h.css';
import '../../css/s/srysnc0xq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f1l3kib5h"/><path class="srysnc0xq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:skyscraper-20" {...props}></Icon>
