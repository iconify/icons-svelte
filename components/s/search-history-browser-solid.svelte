<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7oqmmyvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s7oqmmyvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:search-history-browser-solid" {...props}></Icon>
