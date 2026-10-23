<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu3j9k8yt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cu3j9k8yt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:tablets" {...props}></Icon>
