<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgk_62bzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pgk_62bzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sort-time-filled" {...props}></Icon>
