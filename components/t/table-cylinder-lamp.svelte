<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdajy4bjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdajy4bjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:table-cylinder-lamp" {...props}></Icon>
