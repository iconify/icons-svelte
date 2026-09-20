<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd2khn9on.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vd2khn9on"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:submodule" {...props}></Icon>
