<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7wt4vh5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7wt4vh5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:switch-vertical" {...props}></Icon>
