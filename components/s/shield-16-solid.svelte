<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyf44c-ad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fyf44c-ad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:shield-16-solid" {...props}></Icon>
