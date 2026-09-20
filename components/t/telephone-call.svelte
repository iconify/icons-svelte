<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fokxw6bem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fokxw6bem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:telephone-call" {...props}></Icon>
