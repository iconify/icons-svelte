<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sj5j8p_9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sj5j8p_9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:skateboard" {...props}></Icon>
