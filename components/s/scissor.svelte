<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/la20gcqdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="la20gcqdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:scissor" {...props}></Icon>
