<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo-zs0bum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zo-zs0bum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:set-square" {...props}></Icon>
