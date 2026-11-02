<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgb2gq02p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgb2gq02p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:screenshot-fill" {...props}></Icon>
