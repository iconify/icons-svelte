<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn2cgpf3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fn2cgpf3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:store" {...props}></Icon>
