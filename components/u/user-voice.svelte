<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eck_0ccib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eck_0ccib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:user-voice" {...props}></Icon>
