<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6oytwb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="j6oytwb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:sunset-fill" {...props}></Icon>
