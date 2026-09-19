<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz9ucbcni.css';
import '../../css/g/g7k394syz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="wz9ucbcni"/><path class="g7k394syz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:speaker" {...props}></Icon>
