<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5jd9gutu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="o5jd9gutu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:sand-glass-filled" {...props}></Icon>
