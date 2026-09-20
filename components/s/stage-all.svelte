<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5daksowh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e5daksowh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:stage-all" {...props}></Icon>
