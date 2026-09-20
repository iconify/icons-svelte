<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euw5bu_9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="euw5bu_9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-warning-line" {...props}></Icon>
