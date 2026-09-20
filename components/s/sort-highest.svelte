<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-5ryxzgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="k-5ryxzgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:sort-highest" {...props}></Icon>
