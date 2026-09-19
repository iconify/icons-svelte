<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agw51bipm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="agw51bipm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:zoom-minus" {...props}></Icon>
