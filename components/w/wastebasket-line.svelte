<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n45agrteq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n45agrteq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wastebasket-line" {...props}></Icon>
