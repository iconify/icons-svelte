<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbi7h77fq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbi7h77fq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:smrt" {...props}></Icon>
