<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agnf6sbxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="agnf6sbxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:screenmirroring-filled" {...props}></Icon>
