<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adn9gv48n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="adn9gv48n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:search" {...props}></Icon>
