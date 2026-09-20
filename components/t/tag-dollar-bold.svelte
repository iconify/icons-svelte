<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqk8hyryo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xqk8hyryo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:tag-dollar-bold" {...props}></Icon>
