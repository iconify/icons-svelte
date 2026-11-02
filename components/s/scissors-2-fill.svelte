<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzq-0irrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzq-0irrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:scissors-2-fill" {...props}></Icon>
