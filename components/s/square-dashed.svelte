<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afo9k_fki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afo9k_fki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:square-dashed" {...props}></Icon>
