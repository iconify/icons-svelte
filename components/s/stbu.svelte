<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx-jwkb3l.css';
import '../../css/a/ackwpdbbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yx-jwkb3l"/><path class="ackwpdbbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:stbu" {...props}></Icon>
