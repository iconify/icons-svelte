<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfd4xlzix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qfd4xlzix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:seedling" {...props}></Icon>
