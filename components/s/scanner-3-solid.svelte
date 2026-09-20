<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0crblb7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="o0crblb7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:scanner-3-solid" {...props}></Icon>
