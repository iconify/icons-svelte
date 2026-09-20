<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbny_actr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pbny_actr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:triangle-flag-solid" {...props}></Icon>
