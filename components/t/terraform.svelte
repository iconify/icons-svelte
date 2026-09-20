<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwwg9_gwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lwwg9_gwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:terraform" {...props}></Icon>
