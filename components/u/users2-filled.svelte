<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbrgv8z2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbrgv8z2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:users2-filled" {...props}></Icon>
