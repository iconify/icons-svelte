<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr2ui3bao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="nr2ui3bao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:umbrella" {...props}></Icon>
