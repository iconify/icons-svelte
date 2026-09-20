<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmd7ifbkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cmd7ifbkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sort-number-desc" {...props}></Icon>
