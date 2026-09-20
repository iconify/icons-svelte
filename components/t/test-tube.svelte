<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh8car4ex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lh8car4ex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:test-tube" {...props}></Icon>
