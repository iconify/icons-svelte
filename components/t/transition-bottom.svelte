<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzn5nb1wq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mzn5nb1wq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:transition-bottom" {...props}></Icon>
