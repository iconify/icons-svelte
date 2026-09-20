<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgt55-51t.css';
import '../../css/j/jratsslgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgt55-51t"/><path class="jratsslgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:screw-nut-light" {...props}></Icon>
