<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za9unubkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="za9unubkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:smoke-detector-solid" {...props}></Icon>
