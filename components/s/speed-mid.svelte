<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3p2f3b8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c3p2f3b8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:speed-mid" {...props}></Icon>
