<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9bav7b-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t9bav7b-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:suitcase-lg-fill" {...props}></Icon>
