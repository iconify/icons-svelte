<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp9136o6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pp9136o6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:setting2-filled" {...props}></Icon>
