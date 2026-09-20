<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6t5k5bap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y6t5k5bap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:square-arrow-left2-filled" {...props}></Icon>
