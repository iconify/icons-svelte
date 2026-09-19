<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eu11l_tog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="eu11l_tog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:television-flat-screen" {...props}></Icon>
