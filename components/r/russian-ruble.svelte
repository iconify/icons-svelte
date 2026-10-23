<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t00v4ta5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t00v4ta5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:russian-ruble" {...props}></Icon>
