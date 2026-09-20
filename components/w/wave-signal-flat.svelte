<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3q9_5bnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x3q9_5bnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:wave-signal-flat" {...props}></Icon>
