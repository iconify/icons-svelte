<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izck_4u8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izck_4u8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:venus-and-mars" {...props}></Icon>
