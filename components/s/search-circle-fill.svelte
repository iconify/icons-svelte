<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxp2azrgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="rxp2azrgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:search-circle-fill" {...props}></Icon>
