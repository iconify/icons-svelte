<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5e7-8b-p.css';
import '../../css/q/qrtxhqwfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b5e7-8b-p"/><path class="qrtxhqwfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:user-account" {...props}></Icon>
