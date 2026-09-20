<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st267to5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="st267to5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:search-results" {...props}></Icon>
