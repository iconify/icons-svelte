<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yshpki_ni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yshpki_ni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-asterisk-solid" {...props}></Icon>
