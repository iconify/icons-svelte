<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7pc8fbpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="w7pc8fbpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:target-3-solid" {...props}></Icon>
