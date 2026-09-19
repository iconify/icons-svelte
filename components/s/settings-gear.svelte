<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg8k5ebzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jg8k5ebzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:settings-gear" {...props}></Icon>
