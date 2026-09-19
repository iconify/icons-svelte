<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cebocs6cz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cebocs6cz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:see-no-evil-monkey" {...props}></Icon>
