<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg18jvbqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jg18jvbqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:vim-normal-mode-16" {...props}></Icon>
