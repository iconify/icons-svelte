<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aaa7_e53b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aaa7_e53b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:wrap-text" {...props}></Icon>
