<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e50zsvy-u.css';
import '../../css/f/f-c4afb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="e50zsvy-u"/><path class="f-c4afb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:sort-alphabetical" {...props}></Icon>
