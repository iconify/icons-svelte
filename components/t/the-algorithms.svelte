<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmtzif1hb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xmtzif1hb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:the-algorithms" {...props}></Icon>
