<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhc5occtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lhc5occtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:solid-line-01" {...props}></Icon>
