<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngdodkbms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ngdodkbms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:video-off-fill-16" {...props}></Icon>
