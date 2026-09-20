<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa6legbum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oa6legbum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:skip-forward-outline" {...props}></Icon>
