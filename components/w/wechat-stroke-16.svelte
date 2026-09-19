<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqfh78bki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jqfh78bki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:wechat-stroke-16" {...props}></Icon>
