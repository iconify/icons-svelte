<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2j54kbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c2j54kbue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:sort-z-to-a-filled" {...props}></Icon>
