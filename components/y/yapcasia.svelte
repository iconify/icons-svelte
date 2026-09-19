<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6i3yx5qo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":800,"height":702};
const content = `<path class="e6i3yx5qo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:yapcasia" {...props}></Icon>
