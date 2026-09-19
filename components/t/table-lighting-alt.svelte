<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itdk79b4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itdk79b4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:table-lighting-alt" {...props}></Icon>
