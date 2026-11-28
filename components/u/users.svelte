<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0jqp-b9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0jqp-b9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:users" {...props}></Icon>
