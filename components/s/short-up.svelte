<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t436v9fxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t436v9fxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:short-up" {...props}></Icon>
