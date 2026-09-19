<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqq8e0bjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqq8e0bjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:window-terminal" {...props}></Icon>
