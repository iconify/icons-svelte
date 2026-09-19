<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv_1hsb5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cv_1hsb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:wrenchalt" {...props}></Icon>
