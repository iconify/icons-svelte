<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp_nqwbll.css';
import '../../css/p/p99jesbkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sp_nqwbll"/><path class="p99jesbkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:start-cog" {...props}></Icon>
