<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cut4v5iaq.css';
import '../../css/v/vcq9e7hte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cut4v5iaq"/><path class="vcq9e7hte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:translation-deleted-fill-16" {...props}></Icon>
