<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6_l66cbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6_l66cbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:windows-fill" {...props}></Icon>
