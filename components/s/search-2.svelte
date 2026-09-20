<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3_kvuzgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3_kvuzgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:search-2" {...props}></Icon>
