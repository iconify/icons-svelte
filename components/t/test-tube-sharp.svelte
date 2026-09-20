<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxcqmib8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxcqmib8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:test-tube-sharp" {...props}></Icon>
