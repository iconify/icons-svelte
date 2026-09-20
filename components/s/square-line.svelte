<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3tj9_bai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3tj9_bai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:square-line" {...props}></Icon>
