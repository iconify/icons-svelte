<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvx9mlbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fvx9mlbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:unlock2" {...props}></Icon>
