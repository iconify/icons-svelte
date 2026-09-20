<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7-wzsbyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y7-wzsbyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:script-minus" {...props}></Icon>
