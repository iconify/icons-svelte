<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnqkebwle.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hnqkebwle"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:speed-low-filled" {...props}></Icon>
