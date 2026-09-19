<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3n_pobto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="a3n_pobto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:umbrella" {...props}></Icon>
