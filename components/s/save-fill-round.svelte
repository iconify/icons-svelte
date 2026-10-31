<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nley873cf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nley873cf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:save-fill-round" {...props}></Icon>
