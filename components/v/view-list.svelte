<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehw5kccqx.css';
import '../../css/i/irv3-cbsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ehw5kccqx"/><path class="irv3-cbsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:view-list" {...props}></Icon>
