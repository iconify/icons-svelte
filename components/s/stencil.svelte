<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqg9bfjkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqg9bfjkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:stencil" {...props}></Icon>
