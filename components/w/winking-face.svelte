<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhzkfkbjg.css';
import '../../css/b/b0u2a7nui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lhzkfkbjg"/><path clip-rule="evenodd" class="b0u2a7nui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:winking-face" {...props}></Icon>
