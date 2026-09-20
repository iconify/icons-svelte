<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3n-ye13m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v3n-ye13m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:typewriter-solid" {...props}></Icon>
