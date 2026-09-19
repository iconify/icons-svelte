<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyc5hev-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yyc5hev-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-minus-bold" {...props}></Icon>
