<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbwpj6mtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbwpj6mtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:stroke-style-dotted" {...props}></Icon>
