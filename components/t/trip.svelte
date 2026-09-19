<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/powe_1b0z.css';
import '../../css/s/supz4n9yl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="powe_1b0z"/><path class="supz4n9yl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:trip" {...props}></Icon>
