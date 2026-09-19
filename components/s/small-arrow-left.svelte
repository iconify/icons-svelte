<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2yezpb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":210,"height":700};
const content = `<path class="b2yezpb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:small-arrow-left" {...props}></Icon>
