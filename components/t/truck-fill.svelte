<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbasz78dg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbasz78dg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:truck-fill" {...props}></Icon>
