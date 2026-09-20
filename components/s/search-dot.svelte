<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uep2s2b1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uep2s2b1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:search-dot" {...props}></Icon>
