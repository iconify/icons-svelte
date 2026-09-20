<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll-v7cc5a.css';
import '../../css/t/t7ok3w4ym.css';
import '../../css/o/onfmwrbco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ll-v7cc5a"/><path class="t7ok3w4ym"/><path class="onfmwrbco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:xyo" {...props}></Icon>
