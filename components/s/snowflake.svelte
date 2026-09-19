<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krtijo-qd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="krtijo-qd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:snowflake" {...props}></Icon>
