<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9kitqbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="b9kitqbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:yuan-solid" {...props}></Icon>
