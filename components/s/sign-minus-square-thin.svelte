<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etw8_08xb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="etw8_08xb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-minus-square-thin" {...props}></Icon>
