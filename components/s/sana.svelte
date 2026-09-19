<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akr4lobep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="akr4lobep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sana" {...props}></Icon>
