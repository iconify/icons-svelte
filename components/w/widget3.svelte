<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w17_hf4ys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w17_hf4ys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:widget3" {...props}></Icon>
