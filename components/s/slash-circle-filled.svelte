<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lo5247bgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lo5247bgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:slash-circle-filled" {...props}></Icon>
