<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-q-dlheo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="z-q-dlheo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:wallet-solid" {...props}></Icon>
