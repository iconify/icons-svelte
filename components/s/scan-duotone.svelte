<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auf8n_bsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="auf8n_bsy primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:scan-duotone" {...props}></Icon>
