<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkmhukbwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":700,"height":704};
const content = `<path class="dkmhukbwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:wordpress" {...props}></Icon>
