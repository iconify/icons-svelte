<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3q760j9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d3q760j9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:sun-solid" {...props}></Icon>
