<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urs5c65ih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="urs5c65ih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-letter-k-filled" {...props}></Icon>
