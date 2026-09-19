<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c405ufbaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c405ufbaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:spinner-two-alt" {...props}></Icon>
