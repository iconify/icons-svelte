<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7yns9bkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o7yns9bkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:settings-7-fill" {...props}></Icon>
