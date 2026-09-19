<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfxaipb-q.css';
import '../../css/e/ez6lwcbzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfxaipb-q"/><path class="ez6lwcbzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:school" {...props}></Icon>
