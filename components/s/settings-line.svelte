<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2pyozvqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a2pyozvqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:settings-line" {...props}></Icon>
