<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rivaf_4hs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rivaf_4hs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:shield-exclamation" {...props}></Icon>
