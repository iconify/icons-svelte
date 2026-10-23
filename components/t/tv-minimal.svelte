<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isr074bnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="isr074bnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:tv-minimal" {...props}></Icon>
