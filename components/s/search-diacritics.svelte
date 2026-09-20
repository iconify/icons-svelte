<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7h67eb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q7h67eb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:search-diacritics" {...props}></Icon>
