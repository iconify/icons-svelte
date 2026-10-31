<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/na34i4bqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="na34i4bqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:unlock-gloss" {...props}></Icon>
