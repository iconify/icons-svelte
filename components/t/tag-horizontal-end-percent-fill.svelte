<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnxapybom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nnxapybom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:tag-horizontal-end-percent-fill" {...props}></Icon>
