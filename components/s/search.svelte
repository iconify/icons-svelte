<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlgy_-b2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nlgy_-b2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:search" {...props}></Icon>
