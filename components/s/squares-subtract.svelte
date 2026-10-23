<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl9oq0t4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zl9oq0t4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:squares-subtract" {...props}></Icon>
