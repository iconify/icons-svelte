<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8mdzn34t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8mdzn34t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:tree-catalog" {...props}></Icon>
