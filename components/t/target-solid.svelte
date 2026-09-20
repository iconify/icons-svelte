<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akx7xqakw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="akx7xqakw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:target-solid" {...props}></Icon>
