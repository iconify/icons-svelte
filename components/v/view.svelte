<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvyzhcstg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":795,"height":614};
const content = `<path class="uvyzhcstg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:view" {...props}></Icon>
