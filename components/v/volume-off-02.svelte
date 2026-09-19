<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9q10zbqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m9q10zbqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:volume-off-02" {...props}></Icon>
