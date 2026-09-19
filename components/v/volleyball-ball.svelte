<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id5a9xwyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="id5a9xwyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:volleyball-ball" {...props}></Icon>
