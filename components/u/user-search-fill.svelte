<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-hyrpbgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-hyrpbgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:user-search-fill" {...props}></Icon>
