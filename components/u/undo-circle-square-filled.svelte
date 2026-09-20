<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l25s7qq7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l25s7qq7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:undo-circle-square-filled" {...props}></Icon>
