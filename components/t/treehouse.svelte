<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0980kf7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":24};
const content = `<path class="b0980kf7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:treehouse" {...props}></Icon>
