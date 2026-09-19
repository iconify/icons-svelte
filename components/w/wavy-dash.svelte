<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b83gw5wch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="b83gw5wch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:wavy-dash" {...props}></Icon>
