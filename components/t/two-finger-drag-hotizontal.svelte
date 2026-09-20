<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkiwk6lcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="nkiwk6lcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:two-finger-drag-hotizontal" {...props}></Icon>
