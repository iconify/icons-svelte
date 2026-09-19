<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnrwt8bgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pnrwt8bgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:sound-on" {...props}></Icon>
