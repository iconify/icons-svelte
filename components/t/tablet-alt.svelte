<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvd82_bvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":18,"height":24};
const content = `<path class="xvd82_bvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:tablet-alt" {...props}></Icon>
