<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sglw8166b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sglw8166b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:search-bar-solid" {...props}></Icon>
