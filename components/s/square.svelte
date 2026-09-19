<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3g8599er.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="l3g8599er"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:square" {...props}></Icon>
