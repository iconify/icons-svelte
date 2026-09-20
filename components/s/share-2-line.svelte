<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afdexh4fv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afdexh4fv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:share-2-line" {...props}></Icon>
