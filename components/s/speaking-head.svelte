<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt05xqbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bt05xqbsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:speaking-head" {...props}></Icon>
