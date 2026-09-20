<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2-ckur5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c2-ckur5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:vending-machine-with-question-mark" {...props}></Icon>
