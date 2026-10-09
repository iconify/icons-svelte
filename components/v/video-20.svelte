<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9d68gmeo.css';
import '../../css/z/zuvofvbzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u9d68gmeo"/><path class="zuvofvbzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:video-20" {...props}></Icon>
