<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja1pydb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ja1pydb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:type-h6" {...props}></Icon>
