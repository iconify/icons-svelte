<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-3r2wvvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b-3r2wvvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:wrench" {...props}></Icon>
