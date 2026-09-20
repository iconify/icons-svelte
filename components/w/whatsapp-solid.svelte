<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7_awqbha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f7_awqbha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:whatsapp-solid" {...props}></Icon>
