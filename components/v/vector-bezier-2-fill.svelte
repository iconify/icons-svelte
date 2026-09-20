<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajasrw1yc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ajasrw1yc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:vector-bezier-2-fill" {...props}></Icon>
