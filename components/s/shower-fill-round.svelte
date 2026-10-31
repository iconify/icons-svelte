<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phii_pblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="phii_pblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shower-fill-round" {...props}></Icon>
