<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjey5--pg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zjey5--pg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:wear-gloves" {...props}></Icon>
