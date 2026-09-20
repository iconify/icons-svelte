<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avy6npblp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avy6npblp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:society6" {...props}></Icon>
