<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbcooh8ej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kbcooh8ej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:signage-1-solid" {...props}></Icon>
