<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7yaiqbkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u7yaiqbkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:work-item-requirement" {...props}></Icon>
