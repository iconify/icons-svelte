<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5sa4cbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5sa4cbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:text-underline-wave" {...props}></Icon>
