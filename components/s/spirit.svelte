<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/coopzbbjy.css';
import '../../css/n/nr--xqbvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="coopzbbjy"/><path clip-rule="evenodd" class="nr--xqbvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:spirit" {...props}></Icon>
