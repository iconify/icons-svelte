<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spr61w0uo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="spr61w0uo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sort-down" {...props}></Icon>
