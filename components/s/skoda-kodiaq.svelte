<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9y3e2baj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9y3e2baj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:skoda-kodiaq" {...props}></Icon>
