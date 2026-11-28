<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ght3uszuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ght3uszuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:window-check" {...props}></Icon>
