<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isrc4zxns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="isrc4zxns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:table-column-plus-before" {...props}></Icon>
