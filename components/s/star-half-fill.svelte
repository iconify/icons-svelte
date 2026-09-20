<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijg_ljbou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijg_ljbou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:star-half-fill" {...props}></Icon>
