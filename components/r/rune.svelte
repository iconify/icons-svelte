<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/taydys9dc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="taydys9dc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:rune" {...props}></Icon>
