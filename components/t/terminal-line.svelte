<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m04pxts8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="m04pxts8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:terminal-line" {...props}></Icon>
