<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmjay1pmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bmjay1pmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:search-plus" {...props}></Icon>
