<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s11-_tb9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="s11-_tb9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:sort-lowest" {...props}></Icon>
