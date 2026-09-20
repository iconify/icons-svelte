<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5t6nbb6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="b5t6nbb6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:sound-recognition-search-remix" {...props}></Icon>
