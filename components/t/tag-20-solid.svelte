<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iolwtibcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="iolwtibcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:tag-20-solid" {...props}></Icon>
