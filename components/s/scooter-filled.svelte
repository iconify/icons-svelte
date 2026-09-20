<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9-lygkzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9-lygkzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:scooter-filled" {...props}></Icon>
