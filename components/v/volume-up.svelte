<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti7n7f08l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ti7n7f08l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:volume-up" {...props}></Icon>
