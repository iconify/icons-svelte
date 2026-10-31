<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4_8j7lyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="n4_8j7lyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:star-half-16-solid" {...props}></Icon>
