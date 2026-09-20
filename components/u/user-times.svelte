<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n95vlaczn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n95vlaczn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:user-times" {...props}></Icon>
