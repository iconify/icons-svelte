<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8n6hxosg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="b8n6hxosg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:status-waiting" {...props}></Icon>
