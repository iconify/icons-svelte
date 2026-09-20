<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t71a1jbbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t71a1jbbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:turkey" {...props}></Icon>
