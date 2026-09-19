<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0hb5pbrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i0hb5pbrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:zwavejs" {...props}></Icon>
