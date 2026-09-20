<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds6o01r6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ds6o01r6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:square-arrows-right" {...props}></Icon>
