<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv7os6knc.css';
import '../../css/x/x8o3q-boh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lv7os6knc"/><path class="x8o3q-boh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:triangle" {...props}></Icon>
