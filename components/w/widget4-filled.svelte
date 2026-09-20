<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp5ll4bap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jp5ll4bap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:widget4-filled" {...props}></Icon>
