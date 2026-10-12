<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pigk12xyw.css';
import '../../css/y/y_8olsb-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pigk12xyw"/><path clip-rule="evenodd" class="y_8olsb-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:torus-filled" {...props}></Icon>
