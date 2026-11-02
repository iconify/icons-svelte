<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvvqedcxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvvqedcxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:train-4-fill" {...props}></Icon>
