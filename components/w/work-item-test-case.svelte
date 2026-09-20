<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blwwl03cq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="blwwl03cq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:work-item-test-case" {...props}></Icon>
