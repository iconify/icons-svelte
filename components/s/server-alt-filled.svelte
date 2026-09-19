<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpl_zydug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rpl_zydug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:server-alt-filled" {...props}></Icon>
