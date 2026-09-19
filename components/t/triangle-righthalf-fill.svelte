<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlbqyv7xh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="jlbqyv7xh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:triangle-righthalf-fill" {...props}></Icon>
