<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inequvbxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="inequvbxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:section-sign-16-solid" {...props}></Icon>
