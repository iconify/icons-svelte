<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-lm1hbpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-lm1hbpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:swap-2-line" {...props}></Icon>
