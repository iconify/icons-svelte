<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w03eki6yi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="w03eki6yi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:search-alt" {...props}></Icon>
