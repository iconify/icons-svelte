<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejp8e72nh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ejp8e72nh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:spam" {...props}></Icon>
