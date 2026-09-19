<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thj720svm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="thj720svm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:tablet" {...props}></Icon>
