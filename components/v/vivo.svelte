<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6ef6w-6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t6ef6w-6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vivo" {...props}></Icon>
