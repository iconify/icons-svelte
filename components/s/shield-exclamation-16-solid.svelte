<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijq4veb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ijq4veb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:shield-exclamation-16-solid" {...props}></Icon>
