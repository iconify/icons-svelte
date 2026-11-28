<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogqe36bjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ogqe36bjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:trending-up-solid" {...props}></Icon>
