<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qquw4llwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qquw4llwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:users-gear" {...props}></Icon>
