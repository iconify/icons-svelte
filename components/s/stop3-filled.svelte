<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w88437emw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w88437emw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:stop3-filled" {...props}></Icon>
