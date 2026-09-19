<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrk2n349e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="nrk2n349e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:thought-balloon" {...props}></Icon>
