<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqwmo6byc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqwmo6byc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:thought-line" {...props}></Icon>
