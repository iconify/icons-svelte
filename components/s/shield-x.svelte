<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tup9x39uj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tup9x39uj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:shield-x" {...props}></Icon>
