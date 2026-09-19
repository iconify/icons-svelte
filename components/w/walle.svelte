<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0mz9jkmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c0mz9jkmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:walle" {...props}></Icon>
