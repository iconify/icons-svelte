<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta27mrdhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":18,"height":24};
const content = `<path class="ta27mrdhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:tinder" {...props}></Icon>
