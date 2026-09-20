<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8fzfkb4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8fzfkb4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:suzuki" {...props}></Icon>
