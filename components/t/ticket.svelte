<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prbcqzb6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="prbcqzb6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:ticket" {...props}></Icon>
