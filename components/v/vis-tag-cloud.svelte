<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4nkhhbdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y4nkhhbdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:vis-tag-cloud" {...props}></Icon>
