<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usi-x5bch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="usi-x5bch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:spam-3-fill" {...props}></Icon>
