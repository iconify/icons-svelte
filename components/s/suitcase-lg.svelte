<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i165b5bqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i165b5bqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:suitcase-lg" {...props}></Icon>
