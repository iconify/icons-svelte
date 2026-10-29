<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftxpljb2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ftxpljb2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shield-plus-solid" {...props}></Icon>
