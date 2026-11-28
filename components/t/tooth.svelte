<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-21abmhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-21abmhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tooth" {...props}></Icon>
