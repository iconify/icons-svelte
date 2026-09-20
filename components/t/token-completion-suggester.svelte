<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1i-fu7vn.css';
import '../../css/y/y5w19acgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e1i-fu7vn"/><path class="y5w19acgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-completion-suggester" {...props}></Icon>
