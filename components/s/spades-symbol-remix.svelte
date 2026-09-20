<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-ck-kbes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g-ck-kbes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:spades-symbol-remix" {...props}></Icon>
